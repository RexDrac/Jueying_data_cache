loss-entropy-coeff: 0.0
imitation-weight: 0.5
critic-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
interpolation: False
expert-num: 4
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
record-start-size: 10000.0
actor-lr: 0.0003
reward-scale: 0.1
joint-interpolation: True
loss-output-smooth-coeff: 0.5
tau: 0.001
Physics-frequency: 1000
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
replay-ratio: 1
total-step-num: 2500000000
max-path-num: 20
bullet-default-PD: False
critic-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
loss-output-diff-coeff: 0
task-weight: 0.5
squash-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-action: True
critic-layer-size: [256, 256]
prioritized-exp-replay: True
actor-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
actor-layer-size: [256, 256]
actor-weight-decay: 1e-06
critic-weight-decay: 1e-06
n-step: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
state-dim: 23
dsr-gait-period: 0.6
epoch-step-num: 5000000
train-step-num: 1
gamma: 0.955
render-eval: False
env-id: HumanoidBalanceFilter-v0
actor-l2-reg: 0.0003
rollout-step-num: 1
action-dim: 12
epoch-num: 500
test-num: 4
HLC-frequency: 25
loss-output-bound-coeff: 0.0
batch-size: 128
max-step-num: 2500000000
dsr-gait-freq: 1.667
replay-buffer-size: 1000000
max-episode-num: 5000000
LLC-frequency: 500
critic-lr: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-train-time: 10
