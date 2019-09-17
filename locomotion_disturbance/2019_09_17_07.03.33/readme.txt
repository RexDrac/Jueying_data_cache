loss-output-bound-coeff: 0.0
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
LLC-frequency: 500
rollout-step-num: 1
gating-index: None
expert-num: 4
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 0.5
train-step-num: 1
max-train-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
expert-index: None
actor-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-step: 5000
dsr-gait-freq: 1.667
state-dim: 23
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
n-step: 1
env-id: HumanoidBalanceFilter-v0
gating-layer-size: [32, 32]
epoch-num: 500
dsr-gait-period: 0.6
replay-ratio: 1
filter-action: True
actor-lr: 0.0003
max-episode-num: 5000000
critic-layer-size: [256, 256]
max-path-num: 20
tau: 0.001
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
replay-buffer-size: 1000000
critic-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
max-test-time: 10
action-dim: 12
imitation-weight: 0.5
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
prioritized-exp-replay: True
critic-weight-decay: 1e-06
task-weight: 0.5
critic-l2-reg: 0.0003
batch-size: 128
test-num: 4
squash-action: True
replay-start-size: 10000
total-step-num: 2500000000
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gamma: 0.955
HLC-frequency: 25
Physics-frequency: 1000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
filter-torque: False
record-start-size: 10000.0
reward-scale: 0.1
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
