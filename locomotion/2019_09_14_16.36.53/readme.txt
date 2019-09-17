squash-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
Physics-frequency: 1000
filter-action: True
imitation-weight: 0.5
replay-start-size: 10000
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
batch-size: 128
max-path-step: 5000
gating-index: None
replay-buffer-size: 1000000
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
task-weight: 0.5
actor-lr: 0.0003
max-episode-num: 5000000
bullet-default-PD: False
actor-l2-reg: 0.0003
record-start-size: 10000.0
action-dim: 12
max-path-num: 20
reward-scale: 0.1
gating-layer-size: [32, 32]
test-num: 4
critic-lr: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
max-step-num: 2500000000
actor-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
max-test-time: 10
filter-torque: False
gamma: 0.955
dsr-gait-freq: 1.667
render-eval: False
HLC-frequency: 25
joint-interpolation: True
actor-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
state-dim: 23
expert-index: None
critic-weight-decay: 1e-06
interpolation: False
rollout-step-num: 1
loss-output-diff-coeff: 0
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 4
epoch-step-num: 5000000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
epoch-num: 500
env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
max-train-time: 10
total-step-num: 2500000000
train-step-num: 1
prioritized-exp-replay: True
dsr-gait-period: 0.6
n-step: 1
critic-layer-size: [256, 256]
